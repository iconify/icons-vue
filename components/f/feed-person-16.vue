<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya6w0mbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ya6w0mbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-person-16" /></template>
