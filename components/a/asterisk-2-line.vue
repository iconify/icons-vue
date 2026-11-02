<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcrelkbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcrelkbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:asterisk-2-line" /></template>
