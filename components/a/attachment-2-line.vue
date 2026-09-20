<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx742i41n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx742i41n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-2-line" /></template>
