<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiap8ebun.css';
import '../../css/k/ka5hixi2k.css';
import '../../css/k/kaxf2trrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="ka5hixi2k"/><path class="kaxf2trrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-ansible" /></template>
