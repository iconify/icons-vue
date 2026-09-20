<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo-v9lp_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo-v9lp_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:floatplane" /></template>
