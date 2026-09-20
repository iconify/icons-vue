<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96cw_iaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v96cw_iaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:imessage-logo-solid" /></template>
