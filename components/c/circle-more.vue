<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2uim_bve.css';
import '../../css/t/t4fyarb9e.css';
import '../../css/r/ravzi7blj.css';
import '../../css/b/b9_uigb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="o2uim_bve"/><circle class="t4fyarb9e"/><circle class="ravzi7blj"/><path class="b9_uigb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-more" /></template>
