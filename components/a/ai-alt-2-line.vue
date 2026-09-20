<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/darp4o0pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="darp4o0pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-alt-2-line" /></template>
