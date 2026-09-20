<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpa3fzbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpa3fzbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-1-filled" /></template>
