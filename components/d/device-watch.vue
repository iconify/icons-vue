<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqdj1_xdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqdj1_xdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch" /></template>
