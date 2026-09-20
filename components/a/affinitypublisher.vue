<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-ua1lxok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ua1lxok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:affinitypublisher" /></template>
