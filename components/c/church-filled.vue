<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav-b3ipr.css';
import '../../css/g/gcy3r1rbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jav-b3ipr"/><path class="gcy3r1rbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:church-filled" /></template>
