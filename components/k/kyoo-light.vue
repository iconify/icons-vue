<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n15170bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n15170bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kyoo-light" /></template>
