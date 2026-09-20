<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3p68vbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3p68vbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-off-outline" /></template>
