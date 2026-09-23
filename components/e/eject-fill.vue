<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2e8wbcsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2e8wbcsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eject-fill" /></template>
