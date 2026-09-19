<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvdj6abuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvdj6abuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bus-alt" /></template>
