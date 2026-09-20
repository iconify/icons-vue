<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a20m1ibfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a20m1ibfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ghost-3-filled" /></template>
