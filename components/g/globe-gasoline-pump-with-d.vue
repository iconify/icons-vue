<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny2qdo2_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ny2qdo2_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:globe-gasoline-pump-with-d" /></template>
