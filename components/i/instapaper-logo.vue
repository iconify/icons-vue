<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbo_8fb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbo_8fb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instapaper-logo" /></template>
