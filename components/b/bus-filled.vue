<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plyre2wxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plyre2wxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bus-filled" /></template>
