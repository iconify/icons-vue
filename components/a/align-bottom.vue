<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7rd3fldd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7rd3fldd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:align-bottom" /></template>
