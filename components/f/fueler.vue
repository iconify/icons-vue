<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kio867beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kio867beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fueler" /></template>
