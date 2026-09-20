<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5_-fllxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5_-fllxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rubel-fill" /></template>
