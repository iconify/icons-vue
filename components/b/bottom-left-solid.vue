<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw9-pfc_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hw9-pfc_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bottom-left-solid" /></template>
