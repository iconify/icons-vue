<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sac_xsb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sac_xsb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-i" /></template>
