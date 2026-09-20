<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4oopynuy.css';
import '../../css/s/sm5_fqxyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p4oopynuy"/><path class="sm5_fqxyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:exit-down" /></template>
