<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p21dizb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p21dizb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:backslash" /></template>
