<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-1rxacqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-1rxacqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-bitbucket" /></template>
