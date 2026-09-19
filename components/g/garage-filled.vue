<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnu-_5bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnu-_5bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:garage-filled" /></template>
