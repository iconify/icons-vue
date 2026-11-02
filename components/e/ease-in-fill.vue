<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v15yy0bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v15yy0bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-fill" /></template>
