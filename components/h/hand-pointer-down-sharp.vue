<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz3n2vbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz3n2vbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-down-sharp" /></template>
