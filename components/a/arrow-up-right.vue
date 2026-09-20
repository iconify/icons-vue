<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgo3yzakc.css';
import '../../css/m/m7lzhdc8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgo3yzakc"/><path class="m7lzhdc8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-up-right" /></template>
