<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9-imr2-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9-imr2-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:award-fill" /></template>
