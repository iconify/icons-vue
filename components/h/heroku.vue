<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaec7bbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eaec7bbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:heroku" /></template>
