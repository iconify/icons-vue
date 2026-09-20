<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adqk91n-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adqk91n-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:history" /></template>
