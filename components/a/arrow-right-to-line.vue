<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9_lqqbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9_lqqbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right-to-line" /></template>
