<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmc5rlb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cmc5rlb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bug-solid" /></template>
