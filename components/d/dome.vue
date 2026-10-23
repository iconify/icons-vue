<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9qjcvzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9qjcvzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dome" /></template>
