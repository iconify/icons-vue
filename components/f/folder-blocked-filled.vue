<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw9r7gbbd.css';
import '../../css/u/ull6c1baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw9r7gbbd"/><path class="ull6c1baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-blocked-filled" /></template>
