<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmbn4-8qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lmbn4-8qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:crop" /></template>
