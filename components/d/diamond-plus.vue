<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbc_il0ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbc_il0ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:diamond-plus" /></template>
