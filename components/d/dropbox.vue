<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzqjaccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":682,"height":694};
const content = `<path class="swzqjaccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dropbox" /></template>
