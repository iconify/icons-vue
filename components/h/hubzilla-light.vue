<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv8hv5_7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bv8hv5_7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hubzilla-light" /></template>
