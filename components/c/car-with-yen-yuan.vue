<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rei8szb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rei8szb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-yen-yuan" /></template>
