<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc86bf0gu.css';
import '../../css/h/htispzbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hc86bf0gu"/><path class="htispzbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-double-down" /></template>
