<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xejdyrxnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xejdyrxnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:drawing-compass" /></template>
