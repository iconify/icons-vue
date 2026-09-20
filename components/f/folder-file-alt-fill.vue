<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqcbebh-l.css';
import '../../css/v/v5tal47iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqcbebh-l"/><path class="v5tal47iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-file-alt-fill" /></template>
