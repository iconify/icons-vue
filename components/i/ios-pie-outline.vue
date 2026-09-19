<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn_mz6b4i.css';
import '../../css/r/rf5rhacdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bn_mz6b4i"/><path class="rf5rhacdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pie-outline" /></template>
