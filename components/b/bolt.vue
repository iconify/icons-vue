<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzy2gq6zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nzy2gq6zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:bolt" /></template>
