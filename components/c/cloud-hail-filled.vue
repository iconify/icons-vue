<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_0y3m6li.css';
import '../../css/b/b6hy8accx.css';
import '../../css/i/igxotebur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_0y3m6li"/><path class="b6hy8accx"/><path class="igxotebur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-hail-filled" /></template>
