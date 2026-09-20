<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ph0ccpa.css';
import '../../css/u/uxitrobbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ph0ccpa"/><path class="uxitrobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:delivery-truck-fill" /></template>
