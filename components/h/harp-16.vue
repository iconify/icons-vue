<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzjyarb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dzjyarb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:harp-16" /></template>
