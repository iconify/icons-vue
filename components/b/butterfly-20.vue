<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7tynrbzb.css';
import '../../css/b/bqqcw45gt.css';
import '../../css/c/clko2h42t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x7tynrbzb"/><path class="bqqcw45gt"/><path class="clko2h42t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:butterfly-20" /></template>
