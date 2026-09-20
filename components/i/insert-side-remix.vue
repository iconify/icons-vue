<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-hs3qeyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n-hs3qeyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:insert-side-remix" /></template>
