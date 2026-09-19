<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6v57ysxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n6v57ysxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:globe-americas" /></template>
