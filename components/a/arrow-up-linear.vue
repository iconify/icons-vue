<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufif6wbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufif6wbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-linear" /></template>
