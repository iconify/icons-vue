<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msi7434ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msi7434ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-right-two-tone" /></template>
