<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvd31abxp.css';
import '../../css/t/ta7rc4bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="ta7rc4bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:line-chart" /></template>
