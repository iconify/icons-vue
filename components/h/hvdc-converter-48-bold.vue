<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkzd28t8y.css';
import '../../css/h/hbji4i9fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkzd28t8y"/><path class="hbji4i9fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hvdc-converter-48-bold" /></template>
