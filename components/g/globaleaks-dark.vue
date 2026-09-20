<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aet668bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aet668bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:globaleaks-dark" /></template>
