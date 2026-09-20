<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x50gudbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x50gudbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:farfetch" /></template>
