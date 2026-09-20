<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upd2fnd6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upd2fnd6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:freebsd" /></template>
