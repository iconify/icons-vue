<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac0nmw1ig.css';
import '../../css/a/alo-6-b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ac0nmw1ig"/><path class="alo-6-b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-coins-filled" /></template>
