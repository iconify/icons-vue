<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izu0r0bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izu0r0bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ace" /></template>
