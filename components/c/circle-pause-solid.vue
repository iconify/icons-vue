<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq7wl2-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq7wl2-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:circle-pause-solid" /></template>
