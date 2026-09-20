<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9247wbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9247wbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lapce" /></template>
