<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btw2aqb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btw2aqb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:desktop-pc-outline" /></template>
