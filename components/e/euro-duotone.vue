<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c14t5ib6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14t5ib6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:euro-duotone" /></template>
