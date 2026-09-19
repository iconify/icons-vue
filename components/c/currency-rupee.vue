<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ej_tn8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ej_tn8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-rupee" /></template>
