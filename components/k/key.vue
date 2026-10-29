<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_32d92c.css';
import '../../css/x/xmfhvr75a.css';
import '../../css/b/bnvu6ybwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_32d92c"/><path class="xmfhvr75a"/><path class="bnvu6ybwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:key" /></template>
