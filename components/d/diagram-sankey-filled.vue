<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inj9pp63n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inj9pp63n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diagram-sankey-filled" /></template>
