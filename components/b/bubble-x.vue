<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt9bn2uhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt9bn2uhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bubble-x" /></template>
