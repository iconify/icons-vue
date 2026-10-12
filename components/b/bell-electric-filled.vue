<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpfoayb6f.css';
import '../../css/z/zp19y9ojo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpfoayb6f"/><path class="zp19y9ojo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-electric-filled" /></template>
