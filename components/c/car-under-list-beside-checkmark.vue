<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3goiveog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n3goiveog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-under-list-beside-checkmark" /></template>
