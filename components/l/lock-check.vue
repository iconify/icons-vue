<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chnjt5ufs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chnjt5ufs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lock-check" /></template>
