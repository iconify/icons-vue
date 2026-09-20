<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z--u7bblr.css';
import '../../css/i/ivxllx4mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z--u7bblr"/><path class="ivxllx4mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check-circle-light" /></template>
