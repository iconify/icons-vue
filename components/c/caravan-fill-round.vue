<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ato9klb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ato9klb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-fill-round" /></template>
