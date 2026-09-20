<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehjrp2gbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ehjrp2gbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-empty-question" /></template>
