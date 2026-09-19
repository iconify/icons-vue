<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rne-a9b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rne-a9b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:battery" /></template>
