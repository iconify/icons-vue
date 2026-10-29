<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdvez0bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdvez0bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:euro-solid" /></template>
