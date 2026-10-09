<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkt9q_b2i.css';
import '../../css/p/pczwsit1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkt9q_b2i"/><path class="pczwsit1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laundry-basket-48" /></template>
