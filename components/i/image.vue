<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo696l5nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bo696l5nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:image" /></template>
