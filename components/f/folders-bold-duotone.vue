<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9lmrblm.css';
import '../../css/p/p0tpqpbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9lmrblm"/><path class="p0tpqpbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folders-bold-duotone" /></template>
