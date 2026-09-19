<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc2bejsmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rc2bejsmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:internet-archive" /></template>
