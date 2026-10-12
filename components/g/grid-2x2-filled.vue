<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4gmojpnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4gmojpnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-2x2-filled" /></template>
