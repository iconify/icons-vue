<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-k2eg3fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-k2eg3fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:drag-squares-horizontal-light" /></template>
