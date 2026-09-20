<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h31y4wrru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h31y4wrru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heroku-dark" /></template>
