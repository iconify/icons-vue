<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soai4mb4s.css';
import '../../css/z/zyhrf5vhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="soai4mb4s"/><path class="zyhrf5vhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:1panel-light" /></template>
