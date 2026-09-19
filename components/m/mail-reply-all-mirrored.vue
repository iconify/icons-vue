<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn9ipccxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fn9ipccxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mail-reply-all-mirrored" /></template>
