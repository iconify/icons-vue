<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0j5jlbnz.css';
import '../../css/l/lhpluxdub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0j5jlbnz"/><path class="lhpluxdub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-cog-filled" /></template>
