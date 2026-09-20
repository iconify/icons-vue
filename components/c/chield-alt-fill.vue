<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju7eqfb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju7eqfb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chield-alt-fill" /></template>
