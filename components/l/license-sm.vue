<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgj_o_0ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="bgj_o_0ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:license-sm" /></template>
