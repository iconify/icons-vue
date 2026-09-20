<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk_enobxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk_enobxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:call-2" /></template>
