<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ij1pbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ij1pbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iota" /></template>
