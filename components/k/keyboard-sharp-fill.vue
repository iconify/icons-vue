<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kan81_beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kan81_beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyboard-sharp-fill" /></template>
