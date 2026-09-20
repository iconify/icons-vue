<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vae0u8-_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vae0u8-_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:commit" /></template>
