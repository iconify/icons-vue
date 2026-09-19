<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avl2890wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avl2890wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-open-outline" /></template>
