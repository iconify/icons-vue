<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkz9z_bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkz9z_bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dots-horizontal-outline" /></template>
