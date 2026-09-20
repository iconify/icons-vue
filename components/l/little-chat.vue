<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otn30pbbb.css';
import '../../css/b/bezz-3_ya.css';
import '../../css/v/v-xbbnb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otn30pbbb"/><path class="bezz-3_ya"/><path class="v-xbbnb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:little-chat" /></template>
