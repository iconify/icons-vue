<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbup0b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppbup0b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:discover" /></template>
