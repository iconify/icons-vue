<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnf8da_ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnf8da_ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bookmark-fill" /></template>
