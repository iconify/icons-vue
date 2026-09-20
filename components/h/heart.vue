<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_l4sznkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_l4sznkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:heart" /></template>
