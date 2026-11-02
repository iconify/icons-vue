<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7fj0wb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7fj0wb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-conical-off-fill" /></template>
