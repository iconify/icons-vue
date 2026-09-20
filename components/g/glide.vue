<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao8yx6wuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao8yx6wuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:glide" /></template>
