<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbh8_acgb.css';
import '../../css/g/gd6ueob5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbh8_acgb"/><path class="gd6ueob5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:check-circle" /></template>
