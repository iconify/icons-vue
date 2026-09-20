<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afz2iulxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afz2iulxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up" /></template>
