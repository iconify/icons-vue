<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwf3d0p4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gwf3d0p4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:basket-minus-outline" /></template>
