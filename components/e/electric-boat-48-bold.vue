<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdtvt3bkl.css';
import '../../css/l/l1gaefbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdtvt3bkl"/><path class="l1gaefbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boat-48-bold" /></template>
