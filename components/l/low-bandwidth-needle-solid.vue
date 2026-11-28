<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmv4wkb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmv4wkb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:low-bandwidth-needle-solid" /></template>
