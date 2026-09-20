<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3-nxcb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3-nxcb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:honour-fill" /></template>
