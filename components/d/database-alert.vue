<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex1raf2lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1raf2lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-alert" /></template>
