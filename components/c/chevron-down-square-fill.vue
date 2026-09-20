<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5xbgz_6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5xbgz_6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-down-square-fill" /></template>
