<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcid6acgw.css';
import '../../css/g/g-fa1j-ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcid6acgw"/><path class="g-fa1j-ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-square-minimalistic-bold-duotone" /></template>
