<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ultdrfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a_ultdrfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eye-outlined" /></template>
