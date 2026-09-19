<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzo6b5oqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzo6b5oqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket" /></template>
