<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze5jguwzp.css';
import '../../css/s/s7t5djz9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ze5jguwzp"/><path class="duoicon-primary-layer s7t5djz9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:approved" /></template>
