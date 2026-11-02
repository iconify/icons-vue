<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giq_2-l1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giq_2-l1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:directions-fill" /></template>
