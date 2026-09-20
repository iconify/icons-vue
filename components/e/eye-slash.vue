<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddw5uz2vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddw5uz2vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:eye-slash" /></template>
