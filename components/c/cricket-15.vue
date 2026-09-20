<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az__ulu8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="az__ulu8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cricket-15" /></template>
