<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbbidnbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bbbidnbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:car-pool" /></template>
