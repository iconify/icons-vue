<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0vfx9bkz.css';
import '../../css/k/kijssacqj.css';
import '../../css/q/qbege6bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0vfx9bkz"/><path class="kijssacqj"/><path class="qbege6bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydraulic-cylinder-48-bold" /></template>
