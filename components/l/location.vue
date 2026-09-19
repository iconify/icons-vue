<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdmxzqbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdmxzqbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:location" /></template>
