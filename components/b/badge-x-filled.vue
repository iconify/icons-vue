<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phxtk3bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phxtk3bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-x-filled" /></template>
