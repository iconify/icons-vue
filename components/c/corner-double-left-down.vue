<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awhk9db1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awhk9db1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-double-left-down" /></template>
