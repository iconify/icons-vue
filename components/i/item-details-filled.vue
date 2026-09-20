<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly9poibxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly9poibxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:item-details-filled" /></template>
