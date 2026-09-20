<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n77f96bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n77f96bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-moon" /></template>
