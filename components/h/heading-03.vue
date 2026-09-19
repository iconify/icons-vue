<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd3ujjbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd3ujjbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading-03" /></template>
