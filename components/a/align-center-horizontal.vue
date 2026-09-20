<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btuydmb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btuydmb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-center-horizontal" /></template>
