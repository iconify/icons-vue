<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz931_bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz931_bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:heading-1-solid" /></template>
