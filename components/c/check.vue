<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edzkd_v0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edzkd_v0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:check" /></template>
