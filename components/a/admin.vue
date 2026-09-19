<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjmqt5btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjmqt5btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:admin" /></template>
