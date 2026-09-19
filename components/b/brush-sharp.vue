<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4nw8f58x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4nw8f58x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:brush-sharp" /></template>
