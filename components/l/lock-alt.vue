<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi9rovle.css';
import '../../css/f/fttkq3t5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pmi9rovle"/><path class="fttkq3t5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:lock-alt" /></template>
