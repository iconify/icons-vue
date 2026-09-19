<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmuni9p9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmuni9p9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:dislike-solid" /></template>
