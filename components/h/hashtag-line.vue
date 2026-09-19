<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v88f60b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="v88f60b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hashtag-line" /></template>
