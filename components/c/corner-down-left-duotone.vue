<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-qoshbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-qoshbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-down-left-duotone" /></template>
