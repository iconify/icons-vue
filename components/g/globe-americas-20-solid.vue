<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovyp-kbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ovyp-kbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-americas-20-solid" /></template>
