<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4asfxowo.css';
import '../../css/x/xqkp-ixqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse transform="rotate(-45 256 256.002)" class="p4asfxowo"/><path class="xqkp-ixqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:american-football-outline" /></template>
