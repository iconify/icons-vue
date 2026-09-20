<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae88cib_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae88cib_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brightness-line" /></template>
