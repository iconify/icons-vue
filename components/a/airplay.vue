<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4gpmc3le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4gpmc3le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:airplay" /></template>
