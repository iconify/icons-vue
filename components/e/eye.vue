<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxbfc96cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="wxbfc96cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:eye" /></template>
