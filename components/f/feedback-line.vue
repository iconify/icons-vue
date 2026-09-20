<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtki5oofd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtki5oofd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:feedback-line" /></template>
