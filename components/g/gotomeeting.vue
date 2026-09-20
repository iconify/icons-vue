<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1nli6baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1nli6baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gotomeeting" /></template>
