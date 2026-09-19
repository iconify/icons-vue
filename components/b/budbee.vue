<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s44cpe4gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s44cpe4gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:budbee" /></template>
