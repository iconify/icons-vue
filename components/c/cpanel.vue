<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpdnk9b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpdnk9b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cpanel" /></template>
