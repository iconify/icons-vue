<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm8d2ebpn.css';
import '../../css/g/grqo4obbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rm8d2ebpn"/><path class="grqo4obbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flip-h" /></template>
