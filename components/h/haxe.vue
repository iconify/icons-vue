<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzo2hibyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzo2hibyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:haxe" /></template>
