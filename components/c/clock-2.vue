<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngm3tioc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rngm3tioc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-2" /></template>
