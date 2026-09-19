<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3_jkqz8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3_jkqz8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dizzy" /></template>
