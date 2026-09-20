<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx2181yer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx2181yer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:laptop" /></template>
