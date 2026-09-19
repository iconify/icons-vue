<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl92h6bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl92h6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:home" /></template>
