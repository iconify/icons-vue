<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao5ewccyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao5ewccyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:burj-khalifa-tower-line" /></template>
