<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rerjc9b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rerjc9b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrows-all-direction" /></template>
