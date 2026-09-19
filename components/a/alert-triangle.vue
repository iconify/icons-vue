<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo961jb7c.css';
import '../../css/k/kit0fd8ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo961jb7c"/><path class="kit0fd8ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alert-triangle" /></template>
