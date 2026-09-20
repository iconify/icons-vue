<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pphbv6qxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pphbv6qxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bell" /></template>
