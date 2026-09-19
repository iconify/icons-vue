<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muygl9lui.css';
import '../../css/r/rg45nfbgg.css';
import '../../css/a/aaogj5ntx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="muygl9lui"/><path class="rg45nfbgg"/><path class="aaogj5ntx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-albums-outline" /></template>
