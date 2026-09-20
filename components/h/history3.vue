<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdeg-9-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdeg-9-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:history3" /></template>
