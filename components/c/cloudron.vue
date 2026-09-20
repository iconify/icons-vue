<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeiv6oacw.css';
import '../../css/c/c2jt5db4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oeiv6oacw"/><path class="c2jt5db4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudron" /></template>
