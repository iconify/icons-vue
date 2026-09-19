<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3gam5wwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3gam5wwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:html-file-01" /></template>
