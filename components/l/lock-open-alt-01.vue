<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x73g-fbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x73g-fbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-open-alt-01" /></template>
