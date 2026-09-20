<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eye58abti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eye58abti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:connector-fill" /></template>
