<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqusacuk.css';
import '../../css/p/pe8xatc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqusacuk"/><path class="pe8xatc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:clock" /></template>
