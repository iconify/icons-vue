<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc192ngyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc192ngyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-dashed-panel-fill" /></template>
