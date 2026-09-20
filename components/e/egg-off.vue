<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl479qbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl479qbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:egg-off" /></template>
