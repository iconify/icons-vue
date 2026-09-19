<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atyg_au2t.css';
import '../../css/p/pf0hmharv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atyg_au2t"/><path class="pf0hmharv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-vuejs" /></template>
