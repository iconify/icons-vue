<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaw6epbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oaw6epbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:easy-redmine-dark" /></template>
