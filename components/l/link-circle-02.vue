<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emfxp9bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emfxp9bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:link-circle-02" /></template>
