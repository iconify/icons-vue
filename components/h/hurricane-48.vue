<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5i-ymejz.css';
import '../../css/x/xgar21b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5i-ymejz"/><path class="xgar21b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hurricane-48" /></template>
