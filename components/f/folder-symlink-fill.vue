<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhvlu6b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vhvlu6b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:folder-symlink-fill" /></template>
