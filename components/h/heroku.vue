<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0b1xbbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d0b1xbbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:heroku" /></template>
