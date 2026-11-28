<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eriz5_bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eriz5_bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevrons-left-right-solid" /></template>
