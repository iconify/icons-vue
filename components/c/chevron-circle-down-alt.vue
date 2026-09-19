<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb6wl9bmp.css';
import '../../css/j/jm1-sfbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb6wl9bmp"/><path class="jm1-sfbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-circle-down-alt" /></template>
