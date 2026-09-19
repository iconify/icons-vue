<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/purru6rav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="purru6rav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:border-style-dashed" /></template>
