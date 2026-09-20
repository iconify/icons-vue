<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv78ugbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv78ugbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cookiecutter" /></template>
