<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y62-vdbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y62-vdbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dip" /></template>
