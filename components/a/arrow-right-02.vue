<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szb_fgbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szb_fgbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-right-02" /></template>
