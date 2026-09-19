<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjk9kmbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="jjk9kmbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:directions" /></template>
