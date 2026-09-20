<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltn6fn7xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltn6fn7xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-fill" /></template>
