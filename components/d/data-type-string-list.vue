<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h134tzmmn.css';
import '../../css/d/dwpr0mcby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h134tzmmn"/><path class="dwpr0mcby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:data-type-string-list" /></template>
