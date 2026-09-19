<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiirhsbnc.css';
import '../../css/f/fsqj1k5yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiirhsbnc"/><path clip-rule="evenodd" class="fsqj1k5yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:login-outline" /></template>
