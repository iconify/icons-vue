<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdr89wbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdr89wbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call" /></template>
