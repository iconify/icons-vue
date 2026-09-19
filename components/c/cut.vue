<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ot29b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ot29b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cut" /></template>
