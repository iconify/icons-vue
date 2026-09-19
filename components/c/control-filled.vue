<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd014-png.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nd014-png"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:control-filled" /></template>
