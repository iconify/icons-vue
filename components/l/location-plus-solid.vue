<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk2hq4bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk2hq4bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:location-plus-solid" /></template>
