<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhstl4bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhstl4bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:dropbox-solid" /></template>
