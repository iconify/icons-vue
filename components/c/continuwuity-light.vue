<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjpiittzj.css';
import '../../css/f/funyg-b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjpiittzj"/><path class="funyg-b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:continuwuity-light" /></template>
