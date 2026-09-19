<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-mjqqb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c-mjqqb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrows-up-down" /></template>
