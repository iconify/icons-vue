<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxu8jsb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxu8jsb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-3x2-filled" /></template>
