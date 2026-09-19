<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e00gdx4ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e00gdx4ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-left" /></template>
