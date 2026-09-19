<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yed5v9b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="yed5v9b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-chimney-user" /></template>
