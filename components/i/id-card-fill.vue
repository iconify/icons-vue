<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-v5erbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-v5erbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:id-card-fill" /></template>
