<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br1-2ibkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br1-2ibkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up-double-s" /></template>
