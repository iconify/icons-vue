<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn5b9sbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fn5b9sbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:comment-alt-filled" /></template>
