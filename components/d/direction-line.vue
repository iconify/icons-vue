<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynen73b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynen73b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:direction-line" /></template>
