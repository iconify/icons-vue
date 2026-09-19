<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7i18xb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z7i18xb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-right-fill-16" /></template>
