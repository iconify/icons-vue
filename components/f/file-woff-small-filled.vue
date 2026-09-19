<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf211bbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cf211bbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff-small-filled" /></template>
