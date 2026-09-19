<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp180xbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp180xbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flash-outline" /></template>
