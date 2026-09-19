<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ea4ublc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="j-ea4ublc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:evernote" /></template>
