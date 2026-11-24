<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjymy35eq.css';
import '../../css/w/w966wlbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjymy35eq"/><path class="w966wlbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hop-off-filled" /></template>
