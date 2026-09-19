<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf2u37s2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zf2u37s2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:details" /></template>
