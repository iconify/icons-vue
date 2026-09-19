<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpw2p007g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpw2p007g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-2-bold" /></template>
