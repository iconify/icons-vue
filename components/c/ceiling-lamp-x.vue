<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax4e94l0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4e94l0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ceiling-lamp-x" /></template>
