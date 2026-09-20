<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5skcqr-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5skcqr-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:inbox-favorite-solid" /></template>
