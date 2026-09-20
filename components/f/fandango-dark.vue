<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcmf__n-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcmf__n-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fandango-dark" /></template>
