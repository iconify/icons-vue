<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_0y3m6li.css';
import '../../css/l/lm3e9jb_v.css';
import '../../css/i/igxotebur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_0y3m6li"/><path class="lm3e9jb_v"/><path class="igxotebur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-hail-filled" /></template>
