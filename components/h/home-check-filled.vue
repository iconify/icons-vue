<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ampfih8jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ampfih8jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-check-filled" /></template>
