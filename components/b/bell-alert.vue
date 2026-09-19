<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psdg_7nuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psdg_7nuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-alert" /></template>
