<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q919_xbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q919_xbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-solid" /></template>
