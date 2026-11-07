<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1kah977l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e1kah977l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-charging-20-solid" /></template>
