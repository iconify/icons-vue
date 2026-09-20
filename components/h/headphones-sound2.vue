<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxm_0qbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxm_0qbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones-sound2" /></template>
