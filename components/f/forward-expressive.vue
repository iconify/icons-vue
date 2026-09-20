<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orkf8rbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orkf8rbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:forward-expressive" /></template>
