<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzlup_paf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":168,"height":954};
const content = `<path class="zzlup_paf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bracketright" /></template>
