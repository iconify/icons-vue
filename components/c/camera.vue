<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7aog5bof.css';
import '../../css/g/gysnikbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7aog5bof"/><path class="gysnikbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:camera" /></template>
