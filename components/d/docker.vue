<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr2v7635b.css';
import '../../css/l/lrjrz-r-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr2v7635b"/><path class="lrjrz-r-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:docker" /></template>
