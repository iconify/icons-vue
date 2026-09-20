<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvpn05bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpn05bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-plus" /></template>
