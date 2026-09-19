<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_6v1tzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly_6v1tzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bell-fill" /></template>
