<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoeck4bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoeck4bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-open" /></template>
