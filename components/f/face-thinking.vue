<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcye7x86p.css';
import '../../css/x/xwx0momul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcye7x86p"/><path class="xwx0momul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-thinking" /></template>
