<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi_56x-la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oi_56x-la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eyebrow-and-eyelashes" /></template>
