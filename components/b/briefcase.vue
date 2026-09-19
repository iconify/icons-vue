<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w16i9i5vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w16i9i5vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:briefcase" /></template>
