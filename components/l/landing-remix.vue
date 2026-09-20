<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdbrh7xmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mdbrh7xmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:landing-remix" /></template>
