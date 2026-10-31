<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqx7c2hlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqx7c2hlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:google-round" /></template>
