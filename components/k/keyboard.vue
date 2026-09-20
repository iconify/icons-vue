<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzsl0mbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="lzsl0mbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:keyboard" /></template>
