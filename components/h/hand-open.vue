<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7sprv35n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l7sprv35n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:hand-open" /></template>
