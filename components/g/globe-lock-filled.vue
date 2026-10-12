<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxlfpzpjb.css';
import '../../css/f/fce5xcc5l.css';
import '../../css/h/hyt904_lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlfpzpjb"/><path clip-rule="evenodd" class="fce5xcc5l"/><path class="hyt904_lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-lock-filled" /></template>
