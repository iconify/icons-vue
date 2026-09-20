<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx4c7k3tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tx4c7k3tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-full-check" /></template>
