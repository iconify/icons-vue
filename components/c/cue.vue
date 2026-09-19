<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0q8216sb.css';
import '../../css/u/uf53occ4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k0q8216sb"/><circle class="uf53occ4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cue" /></template>
