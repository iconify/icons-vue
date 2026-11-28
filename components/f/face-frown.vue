<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro2bzqbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro2bzqbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:face-frown" /></template>
