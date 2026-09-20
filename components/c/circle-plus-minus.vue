<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifep767hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifep767hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-plus-minus" /></template>
