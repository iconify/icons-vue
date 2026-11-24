<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctzf07j2m.css';
import '../../css/a/alo-6-b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctzf07j2m"/><path class="alo-6-b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-coins-filled" /></template>
