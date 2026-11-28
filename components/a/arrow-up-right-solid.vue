<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxmzjib8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxmzjib8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-right-solid" /></template>
