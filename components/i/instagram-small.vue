<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/als9jgl4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="als9jgl4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:instagram-small" /></template>
