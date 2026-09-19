<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzdh5gb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzdh5gb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calculator-solid" /></template>
