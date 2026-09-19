<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvf9oixuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvf9oixuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:captions-filled" /></template>
