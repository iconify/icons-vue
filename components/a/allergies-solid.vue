<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9b9k5mif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9b9k5mif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:allergies-solid" /></template>
