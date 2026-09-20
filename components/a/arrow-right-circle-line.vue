<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxouw4mds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxouw4mds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-right-circle-line" /></template>
