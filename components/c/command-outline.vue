<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9xfavm2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9xfavm2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:command-outline" /></template>
