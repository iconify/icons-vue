<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/disstbc7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="disstbc7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:foursquare-logo-2" /></template>
