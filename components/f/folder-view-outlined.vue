<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m48pxccbl.css';
import '../../css/f/fuwxw7uog.css';
import '../../css/e/ejl28tb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m48pxccbl"/><path class="fuwxw7uog"/><path class="ejl28tb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-view-outlined" /></template>
