<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muy8p_6ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="muy8p_6ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:border" /></template>
