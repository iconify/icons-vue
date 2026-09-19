<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go3e2fbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go3e2fbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-right-small" /></template>
