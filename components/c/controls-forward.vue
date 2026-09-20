<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whnx72bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whnx72bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:controls-forward" /></template>
