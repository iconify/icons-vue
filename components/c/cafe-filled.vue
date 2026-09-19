<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk73dkq3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk73dkq3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cafe-filled" /></template>
