<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt4kxjb1o.css';
import '../../css/w/wckr9kb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt4kxjb1o"/><path class="wckr9kb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-circle-down-outline" /></template>
