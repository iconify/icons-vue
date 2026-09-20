<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mad3lj_un.css';
import '../../css/y/ynyhw8b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mad3lj_un"/><path class="ynyhw8b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-supabase-open" /></template>
