<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1iwlptgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r1iwlptgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-b-filled" /></template>
