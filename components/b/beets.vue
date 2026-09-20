<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqw0fe5oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aqw0fe5oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:beets" /></template>
