<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9scvyboa.css';
import '../../css/y/yyqev4b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9scvyboa"/><path class="yyqev4b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-root-filled" /></template>
