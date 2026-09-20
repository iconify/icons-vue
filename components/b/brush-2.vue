<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48rs9bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="u48rs9bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:brush-2" /></template>
