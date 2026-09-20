<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcd4ixenp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcd4ixenp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:1001tracklists" /></template>
