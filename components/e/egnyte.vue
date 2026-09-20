<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9jijnt_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9jijnt_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:egnyte" /></template>
