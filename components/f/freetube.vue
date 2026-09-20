<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b72h2zs-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b72h2zs-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:freetube" /></template>
