<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3kqxsbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3kqxsbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-minus-solid" /></template>
