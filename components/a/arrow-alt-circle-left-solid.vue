<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss1agp6sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss1agp6sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-alt-circle-left-solid" /></template>
