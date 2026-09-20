<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubntm-bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ubntm-bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bench-backrest" /></template>
