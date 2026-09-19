<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-06mp7dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-06mp7dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:last-fm-alt" /></template>
