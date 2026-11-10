<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kidu-ovak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kidu-ovak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:error-503" /></template>
