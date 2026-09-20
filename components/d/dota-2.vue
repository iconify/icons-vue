<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa-0lzoti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa-0lzoti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dota-2" /></template>
