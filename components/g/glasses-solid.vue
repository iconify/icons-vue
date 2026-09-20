<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic2-dskkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic2-dskkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:glasses-solid" /></template>
