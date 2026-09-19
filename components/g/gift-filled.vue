<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zct_xzbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zct_xzbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:gift-filled" /></template>
