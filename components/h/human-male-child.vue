<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdmdb_bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdmdb_bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-male-child" /></template>
