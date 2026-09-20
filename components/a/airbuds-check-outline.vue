<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw34s-b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw34s-b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-check-outline" /></template>
