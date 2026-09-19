<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_vnw0km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3_vnw0km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:good-one" /></template>
