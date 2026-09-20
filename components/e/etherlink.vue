<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxy5hxwwj.css';
import '../../css/b/b-ya-zbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxy5hxwwj"/><path class="b-ya-zbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:etherlink" /></template>
