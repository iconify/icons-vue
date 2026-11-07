<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdp_xxbiy.css';
import '../../css/z/zutdd9mbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp_xxbiy"/><path clip-rule="evenodd" class="zutdd9mbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-minimalistic-outline" /></template>
