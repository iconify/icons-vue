<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfyrl079f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfyrl079f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:basic-attention-token" /></template>
