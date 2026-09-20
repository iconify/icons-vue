<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txqexvbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txqexvbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-verify" /></template>
