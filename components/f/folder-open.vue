<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrjnsjii.css';
import '../../css/x/xatleqcvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrjnsjii"/><path class="xatleqcvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:folder-open" /></template>
