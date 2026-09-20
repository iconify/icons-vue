<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwy0kfu6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hwy0kfu6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-text-telephone" /></template>
