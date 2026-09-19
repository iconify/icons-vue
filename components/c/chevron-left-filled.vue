<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoeo5dh7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoeo5dh7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-left-filled" /></template>
