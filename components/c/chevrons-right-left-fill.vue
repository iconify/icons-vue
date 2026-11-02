<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5krr30wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5krr30wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-right-left-fill" /></template>
