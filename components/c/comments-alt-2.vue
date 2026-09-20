<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y081e11iz.css';
import '../../css/m/m-mridb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y081e11iz"/><path class="m-mridb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:comments-alt-2" /></template>
