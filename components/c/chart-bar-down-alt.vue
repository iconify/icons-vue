<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn5ygw8-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dn5ygw8-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-down-alt" /></template>
