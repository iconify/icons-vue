<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-u7flbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-u7flbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:git-pull-request-arrow" /></template>
