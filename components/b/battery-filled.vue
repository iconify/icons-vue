<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk2u_7bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vk2u_7bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:battery-filled" /></template>
