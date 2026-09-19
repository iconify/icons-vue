<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k72q-yb3f.css';
import '../../css/d/dd34srmzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k72q-yb3f"/><path class="dd34srmzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:golf-alt" /></template>
