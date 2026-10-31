<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_2e5hb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2e5hb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-small-round" /></template>
