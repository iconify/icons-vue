<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkr4snbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mkr4snbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:edit-plant" /></template>
