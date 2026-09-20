<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbb8jab7i.css';
import '../../css/l/ldmh8bwhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbb8jab7i"/><path class="ldmh8bwhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-alt-solid" /></template>
