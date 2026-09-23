<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vunubjemt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vunubjemt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:equal-not-duotone" /></template>
