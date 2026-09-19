<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uywerpb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uywerpb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-up-outline" /></template>
