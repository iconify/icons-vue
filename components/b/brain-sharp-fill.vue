<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evmbrpbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evmbrpbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain-sharp-fill" /></template>
