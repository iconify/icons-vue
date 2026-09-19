<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2muvqext.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="x2muvqext"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:boxtrapper" /></template>
