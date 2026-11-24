<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztuy0owhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztuy0owhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lens-filled" /></template>
