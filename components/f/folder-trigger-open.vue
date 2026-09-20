<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prl8l2bvy.css';
import '../../css/p/ptfrs5bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prl8l2bvy"/><path class="ptfrs5bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-trigger-open" /></template>
