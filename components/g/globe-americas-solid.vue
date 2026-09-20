<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4kdstqoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="d4kdstqoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:globe-americas-solid" /></template>
