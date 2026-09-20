<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6cqwsbin.css';
import '../../css/w/wc0dofbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6cqwsbin"/><path class="wc0dofbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-add-bold" /></template>
