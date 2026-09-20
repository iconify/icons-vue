<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w91fff93j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w91fff93j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-h" /></template>
