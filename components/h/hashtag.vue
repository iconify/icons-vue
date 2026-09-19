<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9jgs1fzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k9jgs1fzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hashtag" /></template>
