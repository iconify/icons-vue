<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd3-z6bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zd3-z6bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder" /></template>
