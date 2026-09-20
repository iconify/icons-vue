<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnyd66bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnyd66bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broom-sharp" /></template>
