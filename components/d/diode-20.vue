<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztcljccrf.css';
import '../../css/m/mk532_t7l.css';
import '../../css/l/lr4yiccjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ztcljccrf"/><path class="mk532_t7l"/><path class="lr4yiccjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diode-20" /></template>
