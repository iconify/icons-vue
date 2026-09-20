<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1f7ihtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sk1f7ihtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:kiwi-bird" /></template>
