<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3mk2sb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3mk2sb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-triangle-loop-solid" /></template>
