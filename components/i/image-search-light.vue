<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j76-9es3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j76-9es3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-search-light" /></template>
