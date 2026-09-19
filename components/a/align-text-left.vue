<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf20193bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf20193bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-text-left" /></template>
