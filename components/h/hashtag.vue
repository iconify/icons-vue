<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za4ik9b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za4ik9b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hashtag" /></template>
