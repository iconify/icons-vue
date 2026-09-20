<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra13slu7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ra13slu7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:id" /></template>
