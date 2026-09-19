<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a588ydb6o.css';
import '../../css/a/axujlccoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a588ydb6o"/><path class="axujlccoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-baseball" /></template>
