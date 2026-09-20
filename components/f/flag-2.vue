<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8xp7lqmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8xp7lqmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:flag-2" /></template>
