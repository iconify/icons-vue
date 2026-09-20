<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymumgebts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymumgebts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:comp" /></template>
