<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5edn-b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5edn-b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fullscreen-exit" /></template>
