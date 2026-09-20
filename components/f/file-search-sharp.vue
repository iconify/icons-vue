<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvz-i3byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvz-i3byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-search-sharp" /></template>
