<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp6wu9boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp6wu9boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:barcode" /></template>
