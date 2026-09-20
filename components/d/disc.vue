<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu23libwc.css';
import '../../css/a/at1afwblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pu23libwc"/><path class="at1afwblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:disc" /></template>
