<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/artdn7bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="artdn7bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:login" /></template>
