<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ewr3kwo.css';
import '../../css/w/w0fg7jb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ewr3kwo"/><path class="w0fg7jb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:corner-down-left" /></template>
