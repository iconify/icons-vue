<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z79xku0to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z79xku0to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-som" /></template>
