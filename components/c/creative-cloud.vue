<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3k9y0miw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m3k9y0miw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:creative-cloud" /></template>
