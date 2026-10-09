<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5aa0tfys.css';
import '../../css/r/r1qak2b5n.css';
import '../../css/h/h8k7vyb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u5aa0tfys"/><path class="r1qak2b5n"/><path class="h8k7vyb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sync-20" /></template>
