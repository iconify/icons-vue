<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgyr5-bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wgyr5-bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:axe" /></template>
