<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mug5kwbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="mug5kwbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:greenlantern" /></template>
