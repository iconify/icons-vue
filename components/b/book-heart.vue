<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz_dv7bxn.css';
import '../../css/a/aikx1pj2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz_dv7bxn"/><path class="aikx1pj2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:book-heart" /></template>
