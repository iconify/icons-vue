<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to010e9dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="to010e9dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-meh" /></template>
