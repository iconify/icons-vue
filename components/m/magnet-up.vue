<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb759fl4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb759fl4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-up" /></template>
