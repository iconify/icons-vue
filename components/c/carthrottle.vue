<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da_ij5bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_ij5bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:carthrottle" /></template>
