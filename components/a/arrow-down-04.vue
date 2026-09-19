<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihseuibjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihseuibjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-04" /></template>
