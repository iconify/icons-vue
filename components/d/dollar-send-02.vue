<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv-j_2b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv-j_2b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dollar-send-02" /></template>
