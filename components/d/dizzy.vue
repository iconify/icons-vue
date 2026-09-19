<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b35t7ivdn.css';
import '../../css/a/a3u8wvb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b35t7ivdn"/><path class="a3u8wvb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dizzy" /></template>
