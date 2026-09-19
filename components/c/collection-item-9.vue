<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkafytb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="xkafytb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item-9" /></template>
