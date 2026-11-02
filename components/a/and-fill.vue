<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jch0wcbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jch0wcbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:and-fill" /></template>
