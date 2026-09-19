<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhqzwgwvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhqzwgwvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-bottom" /></template>
