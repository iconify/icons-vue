<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udnvt1-ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udnvt1-ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:instagram-alt" /></template>
