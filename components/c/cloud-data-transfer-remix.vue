<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kar-pobqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kar-pobqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-data-transfer-remix" /></template>
