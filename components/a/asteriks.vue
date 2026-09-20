<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7-l_qpoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7-l_qpoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:asteriks" /></template>
