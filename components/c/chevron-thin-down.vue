<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqn8ef0hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqn8ef0hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-thin-down" /></template>
