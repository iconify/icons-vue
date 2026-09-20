<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxopr54xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxopr54xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-2-fill" /></template>
