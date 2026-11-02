<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob4bk-btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob4bk-btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-line" /></template>
