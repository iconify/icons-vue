<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my3unjbkn.css';
import '../../css/y/y8ai33b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="my3unjbkn"/><path class="y8ai33b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:cash" /></template>
