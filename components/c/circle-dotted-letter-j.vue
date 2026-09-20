<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8xzrvbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8xzrvbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-j" /></template>
