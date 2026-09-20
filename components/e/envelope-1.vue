<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ies6qcc_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ies6qcc_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:envelope-1" /></template>
