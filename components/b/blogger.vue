<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6wskbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="dg6wskbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:blogger" /></template>
