<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paer3lxos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="paer3lxos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-peace-bold" /></template>
