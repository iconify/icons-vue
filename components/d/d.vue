<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfae_b7ux.css';
import '../../css/d/dqr3ofb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lfae_b7ux"/><circle class="dqr3ofb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:d" /></template>
