<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ranjxs-at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ranjxs-at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-right-dashed-panel-fill" /></template>
