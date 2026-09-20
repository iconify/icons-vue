<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyoyz9ojw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uyoyz9ojw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book-bookmark" /></template>
