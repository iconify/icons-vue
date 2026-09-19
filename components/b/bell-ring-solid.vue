<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfm-jtbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfm-jtbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bell-ring-solid" /></template>
