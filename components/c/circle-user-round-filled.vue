<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saldzrb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="saldzrb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-user-round-filled" /></template>
