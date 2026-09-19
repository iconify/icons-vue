<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu2p00rwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu2p00rwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:badminton" /></template>
