<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceiehxfky.css';
import '../../css/v/v3pjvgp8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ceiehxfky"/><path class="v3pjvgp8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:form-outlined" /></template>
