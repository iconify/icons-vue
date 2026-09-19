<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeu5_na5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeu5_na5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:linear" /></template>
