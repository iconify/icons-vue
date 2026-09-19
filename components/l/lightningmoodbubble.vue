<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw4hi5b4t.css';
import '../../css/r/r5yjrccli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw4hi5b4t"/><path class="r5yjrccli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lightningmoodbubble" /></template>
