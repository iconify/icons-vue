<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6qf9oyxh.css';
import '../../css/i/i-nkzdl-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6qf9oyxh"/><path class="i-nkzdl-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-adobe-photoshop-filled" /></template>
