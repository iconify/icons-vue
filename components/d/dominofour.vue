<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq6gfzbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="mq6gfzbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominofour" /></template>
