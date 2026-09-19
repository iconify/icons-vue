<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es35w10kr.css';
import '../../css/j/jzeym_btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es35w10kr"/><path class="jzeym_btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:guitar-amp-filled" /></template>
