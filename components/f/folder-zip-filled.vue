<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3t8n_b1o.css';
import '../../css/j/jit9i0epo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3t8n_b1o"/><path class="jit9i0epo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-zip-filled" /></template>
