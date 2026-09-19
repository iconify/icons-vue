<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk84ywhyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk84ywhyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fork" /></template>
