<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4dm_8boq.css';
import '../../css/s/swzjqgj-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s4dm_8boq"/><circle class="swzjqgj-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-warning-stroke-12" /></template>
