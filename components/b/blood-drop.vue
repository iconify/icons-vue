<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pev-oobec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pev-oobec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-drop" /></template>
