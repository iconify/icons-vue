<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d80rk9xbs.css';
import '../../css/m/mp-tddbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d80rk9xbs"/><path clip-rule="evenodd" class="mp-tddbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimlistic-bold" /></template>
