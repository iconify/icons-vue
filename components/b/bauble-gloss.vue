<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isbzjp8fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isbzjp8fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bauble-gloss" /></template>
