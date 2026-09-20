<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_97y5boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_97y5boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:browser-off" /></template>
