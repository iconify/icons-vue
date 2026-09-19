<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2j61makx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="a2j61makx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:default" /></template>
