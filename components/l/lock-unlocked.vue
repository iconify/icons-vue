<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s67jb_bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s67jb_bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:lock-unlocked" /></template>
