<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwty8issf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gwty8issf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bomb-remix" /></template>
