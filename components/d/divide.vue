<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nznd92b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nznd92b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:divide" /></template>
