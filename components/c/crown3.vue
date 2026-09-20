<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko02o0b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko02o0b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crown3" /></template>
