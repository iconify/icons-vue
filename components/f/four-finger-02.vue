<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfxyw729p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfxyw729p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:four-finger-02" /></template>
