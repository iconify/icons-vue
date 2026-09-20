<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuk3ct2rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuk3ct2rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:known" /></template>
