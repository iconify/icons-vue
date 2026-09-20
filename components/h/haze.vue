<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvqhi-bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvqhi-bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:haze" /></template>
