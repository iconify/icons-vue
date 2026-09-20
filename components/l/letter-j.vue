<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp4rj4bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp4rj4bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-j" /></template>
