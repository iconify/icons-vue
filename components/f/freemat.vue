<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkb3kxbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":489,"height":512};
const content = `<path class="bkb3kxbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:freemat" /></template>
