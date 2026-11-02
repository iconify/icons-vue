<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx0rgvnfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx0rgvnfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hashtag-line" /></template>
