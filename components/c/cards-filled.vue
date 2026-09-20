<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfbvigznf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfbvigznf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cards-filled" /></template>
