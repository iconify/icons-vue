<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq9xq1nkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq9xq1nkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:help-square-filled" /></template>
