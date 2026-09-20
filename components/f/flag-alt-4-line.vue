<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7w6txbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7w6txbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-4-line" /></template>
