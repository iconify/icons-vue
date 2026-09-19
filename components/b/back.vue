<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4uk6em5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b4uk6em5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:back" /></template>
