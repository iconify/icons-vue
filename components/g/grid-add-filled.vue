<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdwcty1xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdwcty1xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:grid-add-filled" /></template>
