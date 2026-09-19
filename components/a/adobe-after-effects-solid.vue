<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk39v1bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk39v1bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:adobe-after-effects-solid" /></template>
