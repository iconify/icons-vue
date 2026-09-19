<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-m70vbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="c-m70vbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:kiwi" /></template>
