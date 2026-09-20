<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okkrs1paw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okkrs1paw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-x" /></template>
