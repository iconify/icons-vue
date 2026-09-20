<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc_0qyjkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_0qyjkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-up-filled" /></template>
