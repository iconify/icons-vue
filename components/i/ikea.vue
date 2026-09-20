<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs9p4d8nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs9p4d8nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ikea" /></template>
