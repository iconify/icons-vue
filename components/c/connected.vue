<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tylrpc4_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tylrpc4_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:connected" /></template>
