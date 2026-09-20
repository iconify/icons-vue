<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyftamxxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyftamxxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-fill" /></template>
