<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll2pwacuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll2pwacuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:door-open-filled" /></template>
