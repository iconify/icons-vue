<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epmpu1b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epmpu1b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:between-horizontal-start-filled" /></template>
