<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx3sflbzb.css';
import '../../css/f/fntwqg-7t.css';
import '../../css/b/blgoysbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yx3sflbzb"/><path class="fntwqg-7t"/><path class="blgoysbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:homeassistant-wordmark" /></template>
