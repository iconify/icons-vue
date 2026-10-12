<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfnvfbc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bfnvfbc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-contacts-fill-20" /></template>
