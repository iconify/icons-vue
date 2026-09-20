<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqb3ih61m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqb3ih61m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:edit-pen-2" /></template>
