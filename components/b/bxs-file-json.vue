<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7_amibcp.css';
import '../../css/w/wob-_umgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_amibcp"/><path class="wob-_umgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-json" /></template>
