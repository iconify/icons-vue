<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eruo3-fxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eruo3-fxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-classic-duotone" /></template>
