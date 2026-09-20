<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtjw5snr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wgtjw5snr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:id-card" /></template>
