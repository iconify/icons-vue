<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqkt7bc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqkt7bc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:branch" /></template>
