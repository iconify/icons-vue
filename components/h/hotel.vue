<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqkms_quy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqkms_quy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hotel" /></template>
