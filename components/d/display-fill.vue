<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcftk1tjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcftk1tjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:display-fill" /></template>
