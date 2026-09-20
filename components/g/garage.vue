<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6gff_n3z.css';
import '../../css/p/pnvwxie9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6gff_n3z"/><path class="pnvwxie9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garage" /></template>
