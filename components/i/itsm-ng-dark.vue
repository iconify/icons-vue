<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2urnglye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2urnglye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:itsm-ng-dark" /></template>
