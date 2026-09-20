<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drqwzbcaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drqwzbcaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-right-solid" /></template>
