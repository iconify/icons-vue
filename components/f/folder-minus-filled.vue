<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kegiq1cwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kegiq1cwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-minus-filled" /></template>
