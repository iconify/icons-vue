<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkg4t7ppz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkg4t7ppz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:kickstarter-logo" /></template>
