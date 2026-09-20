<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zevmcubxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zevmcubxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-2-filled" /></template>
