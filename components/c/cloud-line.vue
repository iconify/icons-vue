<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxttk3bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxttk3bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:cloud-line" /></template>
