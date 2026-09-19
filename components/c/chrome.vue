<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj3mtbc7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="dj3mtbc7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:chrome" /></template>
