<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju2t91bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju2t91bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bug-virus-browser-solid" /></template>
