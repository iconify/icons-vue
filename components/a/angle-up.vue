<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8pb41bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8pb41bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:angle-up" /></template>
