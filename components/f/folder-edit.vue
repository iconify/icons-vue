<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-ff30bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-ff30bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-edit" /></template>
