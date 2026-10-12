<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glnvg4bft.css';
import '../../css/v/vqic2ia8z.css';
import '../../css/u/u5f0yi99u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glnvg4bft"/><path clip-rule="evenodd" class="vqic2ia8z"/><path class="u5f0yi99u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hamburger-filled" /></template>
