<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7c84o2ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n7c84o2ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojisorry" /></template>
