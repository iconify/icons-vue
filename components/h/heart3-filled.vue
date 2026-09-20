<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iekxtii2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iekxtii2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart3-filled" /></template>
