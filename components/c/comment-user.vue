<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7ce7h84x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d7ce7h84x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:comment-user" /></template>
