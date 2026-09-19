<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7brlpbnx.css';
import '../../css/x/xz4txmb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7brlpbnx"/><path class="xz4txmb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-shuffle" /></template>
