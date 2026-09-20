<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dazllrb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dazllrb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dota-2" /></template>
