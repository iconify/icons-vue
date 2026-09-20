<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-6r57b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-6r57b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gitpod" /></template>
