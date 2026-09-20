<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob-_cqb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ob-_cqb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:glide" /></template>
