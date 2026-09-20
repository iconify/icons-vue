<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xits50bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xits50bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cloud-rain" /></template>
