<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyf0sk1kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyf0sk1kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-check-sharp-fill" /></template>
