<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibwv3bt8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibwv3bt8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-9" /></template>
