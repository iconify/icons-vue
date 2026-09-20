<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt7jfflff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yt7jfflff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:keycdn" /></template>
