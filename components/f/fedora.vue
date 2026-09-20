<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7gzqcy7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7gzqcy7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fedora" /></template>
