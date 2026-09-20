<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smldc0b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smldc0b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-number-5" /></template>
