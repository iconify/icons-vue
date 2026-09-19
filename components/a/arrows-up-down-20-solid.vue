<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8y__o5bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s8y__o5bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-up-down-20-solid" /></template>
