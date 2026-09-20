<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn93bvb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn93bvb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gxa" /></template>
