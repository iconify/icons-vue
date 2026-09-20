<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7tplmbgr.css';
import '../../css/j/jj8ei-gdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7tplmbgr"/><path class="jj8ei-gdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cru" /></template>
