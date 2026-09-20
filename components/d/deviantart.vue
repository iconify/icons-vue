<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwkfe5ngs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwkfe5ngs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deviantart" /></template>
