<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj2tc7b5c.css';
import '../../css/z/zoxpwbb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tj2tc7b5c"/><path class="zoxpwbb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:briefcase-plus-filled" /></template>
