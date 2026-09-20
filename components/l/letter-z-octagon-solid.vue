<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxsabke1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxsabke1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-z-octagon-solid" /></template>
