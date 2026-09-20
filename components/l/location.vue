<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rue4o98ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rue4o98ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:location" /></template>
