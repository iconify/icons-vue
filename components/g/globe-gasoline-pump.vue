<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbau5pxqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mbau5pxqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:globe-gasoline-pump" /></template>
