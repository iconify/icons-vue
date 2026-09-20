<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ustgjj26u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ustgjj26u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:link-1" /></template>
