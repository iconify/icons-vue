<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcf0a2x-v.css';
import '../../css/y/yr6qxeb0g.css';
import '../../css/l/lrjsqqbbm.css';
import '../../css/c/cd3dpacbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcf0a2x-v"/><path class="yr6qxeb0g"/><path class="lrjsqqbbm"/><path class="cd3dpacbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bell" /></template>
