<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5_tzxbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u5_tzxbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-slash" /></template>
