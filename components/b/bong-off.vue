<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaa5_5o5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa5_5o5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bong-off" /></template>
