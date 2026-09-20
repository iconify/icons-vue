<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyqpj5b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oyqpj5b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-above-waters" /></template>
