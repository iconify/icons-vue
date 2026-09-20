<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtajz45ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtajz45ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-plus-logo-2" /></template>
