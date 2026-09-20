<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae99qnlul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae99qnlul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:files" /></template>
