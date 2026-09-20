<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byem0y19c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="byem0y19c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hospital-h" /></template>
