<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnycbel7f.css';
import '../../css/v/vxg7h7uod.css';
import '../../css/p/poohdx77y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rnycbel7f"/><path class="vxg7h7uod"/><path class="poohdx77y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-rss-outline" /></template>
