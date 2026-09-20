<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdn6t9hua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdn6t9hua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop2-filled" /></template>
