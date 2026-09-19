<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k371edcsm.css';
import '../../css/a/aaxtufr3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k371edcsm"/><path class="aaxtufr3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:badge-exclamation" /></template>
