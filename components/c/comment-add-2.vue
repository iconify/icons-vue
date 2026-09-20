<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxdbhxwdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxdbhxwdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:comment-add-2" /></template>
