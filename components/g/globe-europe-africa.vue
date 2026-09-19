<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pehby3vco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pehby3vco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-europe-africa" /></template>
