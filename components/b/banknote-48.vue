<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shgfqubvu.css';
import '../../css/b/b101e8_sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shgfqubvu"/><path class="b101e8_sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:banknote-48" /></template>
