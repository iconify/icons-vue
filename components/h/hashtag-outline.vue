<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiaujwb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uiaujwb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-outline" /></template>
