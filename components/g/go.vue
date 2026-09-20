<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gumwfk82y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gumwfk82y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:go" /></template>
