<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nre_rzf9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nre_rzf9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:clock" /></template>
