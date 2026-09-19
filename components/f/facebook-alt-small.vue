<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydba-6b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ydba-6b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:facebook-alt-small" /></template>
