<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbwwvpusx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tbwwvpusx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-box-up-20" /></template>
