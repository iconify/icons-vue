<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxj-53b3o.css';
import '../../css/v/vdkkambso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxj-53b3o"/><path class="vdkkambso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-x-circle" /></template>
