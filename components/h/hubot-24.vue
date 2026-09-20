<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zubg1vb6f.css';
import '../../css/x/xivpjuiep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zubg1vb6f"/><path class="xivpjuiep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hubot-24" /></template>
