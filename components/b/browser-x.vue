<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_fa7rqxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_fa7rqxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:browser-x" /></template>
