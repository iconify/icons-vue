<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2nrf10bf.css';
import '../../css/n/nxk8rccaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="nxk8rccaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favorite-star-bold-duotone" /></template>
