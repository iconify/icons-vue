<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3jnswbyn.css';
import '../../css/n/n3b-hhblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jnswbyn"/><path clip-rule="evenodd" class="n3b-hhblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cpu-filled" /></template>
