<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abg_9_bhy.css';
import '../../css/j/j6q_paczc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abg_9_bhy"/><path clip-rule="evenodd" class="j6q_paczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-info" /></template>
