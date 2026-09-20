<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxpv5-bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpv5-bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlecampaignmanager360" /></template>
