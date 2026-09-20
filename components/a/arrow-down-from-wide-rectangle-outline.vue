<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxnfo63mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kxnfo63mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-wide-rectangle-outline" /></template>
