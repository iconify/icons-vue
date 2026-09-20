<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqn_rxbsq.css';
import '../../css/m/mq1ufp71u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jqn_rxbsq"/><path class="mq1ufp71u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:controller" /></template>
