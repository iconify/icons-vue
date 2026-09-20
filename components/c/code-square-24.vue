<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmjreii-g.css';
import '../../css/t/tbcp7-bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjreii-g"/><path class="tbcp7-bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-square-24" /></template>
