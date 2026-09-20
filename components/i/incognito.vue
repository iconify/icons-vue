<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn1cj-w2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn1cj-w2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:incognito" /></template>
