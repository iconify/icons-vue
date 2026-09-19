<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz58jx3gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz58jx3gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-alt" /></template>
