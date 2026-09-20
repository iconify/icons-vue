<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f806y-bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f806y-bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-quetzal" /></template>
