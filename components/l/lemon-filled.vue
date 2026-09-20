<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noxt3rbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noxt3rbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lemon-filled" /></template>
