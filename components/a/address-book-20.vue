<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wi2x_6l.css';
import '../../css/p/pvszaybyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x8wi2x_6l"/><path class="pvszaybyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:address-book-20" /></template>
