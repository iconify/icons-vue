<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s17h1ybel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s17h1ybel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-plus-2" /></template>
