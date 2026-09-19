<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyw2gn6tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyw2gn6tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-meh-blank" /></template>
