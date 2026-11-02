<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia090xb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia090xb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-circle-fill" /></template>
