<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8u_vxo6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8u_vxo6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cube-transparent" /></template>
