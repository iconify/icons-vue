<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylzxcmbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylzxcmbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lightning-line" /></template>
