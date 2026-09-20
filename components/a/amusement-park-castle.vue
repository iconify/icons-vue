<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfduxkh2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfduxkh2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:amusement-park-castle" /></template>
