<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w53pd_q7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w53pd_q7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:airtable-logo" /></template>
