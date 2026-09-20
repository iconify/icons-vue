<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqx72wz7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqx72wz7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brightness-half" /></template>
