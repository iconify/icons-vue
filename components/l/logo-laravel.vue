<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0a1o5sny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0a1o5sny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-laravel" /></template>
