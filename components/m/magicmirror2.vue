<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ydcvb-h.css';
import '../../css/n/n3w0hhuyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1ydcvb-h"/><path class="n3w0hhuyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:magicmirror2" /></template>
