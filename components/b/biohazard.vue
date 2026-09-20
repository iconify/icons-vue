<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an1puqb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an1puqb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biohazard" /></template>
