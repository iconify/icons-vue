<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e30lxvp6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e30lxvp6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-down-long" /></template>
