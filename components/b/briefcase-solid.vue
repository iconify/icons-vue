<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdfevou9k.css';
import '../../css/h/hfrzhebxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qdfevou9k"/><path class="hfrzhebxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:briefcase-solid" /></template>
