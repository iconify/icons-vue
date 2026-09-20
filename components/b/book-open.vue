<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3sus5brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3sus5brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book-open" /></template>
