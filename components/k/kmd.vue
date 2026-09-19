<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmjd7wbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":96,"height":96};
const content = `<path clip-rule="evenodd" class="xmjd7wbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:kmd" /></template>
