<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b71fi303z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b71fi303z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gifts-solid" /></template>
