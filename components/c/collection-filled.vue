<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s87l4gbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s87l4gbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:collection-filled" /></template>
