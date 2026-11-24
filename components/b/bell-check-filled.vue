<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikzgpudrt.css';
import '../../css/d/dxc9wabla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikzgpudrt"/><path class="dxc9wabla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-check-filled" /></template>
