<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyy3pubza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyy3pubza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:droplet-off-outline" /></template>
