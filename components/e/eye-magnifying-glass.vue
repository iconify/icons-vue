<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blc_bco-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="blc_bco-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:eye-magnifying-glass" /></template>
