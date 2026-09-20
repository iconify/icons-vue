<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2yhxw1jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2yhxw1jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-cast" /></template>
