<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axg1wdx3v.css';
import '../../css/n/n5p315boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axg1wdx3v"/><path class="n5p315boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-phone-outgoing" /></template>
