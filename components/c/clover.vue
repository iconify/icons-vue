<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyv3hac8i.css';
import '../../css/x/xg50517th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyv3hac8i"/><path clip-rule="evenodd" class="xg50517th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:clover" /></template>
