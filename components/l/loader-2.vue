<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs7v3hkcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs7v3hkcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:loader-2" /></template>
