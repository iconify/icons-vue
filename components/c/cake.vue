<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqe9-iawx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uqe9-iawx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cake" /></template>
