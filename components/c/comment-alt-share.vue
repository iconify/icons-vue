<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjwnkn-5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjwnkn-5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-share" /></template>
