<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs733r24k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs733r24k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:action" /></template>
