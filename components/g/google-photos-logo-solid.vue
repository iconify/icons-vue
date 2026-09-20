<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5mh2ibhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5mh2ibhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-photos-logo-solid" /></template>
