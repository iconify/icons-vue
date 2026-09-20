<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g99h9zyby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g99h9zyby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rubel-2-fill" /></template>
