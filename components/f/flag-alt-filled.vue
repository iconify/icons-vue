<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0n5v1sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us0n5v1sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flag-alt-filled" /></template>
