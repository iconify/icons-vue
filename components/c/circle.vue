<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmw8fw_wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nmw8fw_wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:circle" /></template>
