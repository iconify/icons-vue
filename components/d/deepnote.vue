<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipb-aqb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipb-aqb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:deepnote" /></template>
