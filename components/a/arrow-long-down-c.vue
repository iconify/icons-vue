<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6xqxmrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd6xqxmrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-down-c" /></template>
