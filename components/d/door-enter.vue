<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-ohd3mqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ohd3mqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:door-enter" /></template>
