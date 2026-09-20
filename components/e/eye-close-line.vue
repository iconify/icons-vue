<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjmgc7bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjmgc7bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-close-line" /></template>
