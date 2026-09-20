<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezm350nac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezm350nac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:habr" /></template>
