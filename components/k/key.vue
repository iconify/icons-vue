<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2p-pcojn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v2p-pcojn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:key" /></template>
