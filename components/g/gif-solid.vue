<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em0hcp2gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em0hcp2gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:gif-solid" /></template>
