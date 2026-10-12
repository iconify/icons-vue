<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktt2-ebbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktt2-ebbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-diagonal-left" /></template>
