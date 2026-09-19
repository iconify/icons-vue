<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z80pyoh0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z80pyoh0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-frown-open" /></template>
