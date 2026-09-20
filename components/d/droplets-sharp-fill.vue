<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2aycgwzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2aycgwzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplets-sharp-fill" /></template>
