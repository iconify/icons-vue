<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnp_xxbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnp_xxbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fence-filled" /></template>
