<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xchmlgbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xchmlgbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:agent-assist" /></template>
