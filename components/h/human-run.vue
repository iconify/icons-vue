<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b13s69bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b13s69bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-run" /></template>
