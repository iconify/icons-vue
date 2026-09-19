<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f87a287-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f87a287-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hamburger-small" /></template>
