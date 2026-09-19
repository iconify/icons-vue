<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br-uotb6n.css';
import '../../css/l/lw6k7rbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br-uotb6n"/><path class="lw6k7rbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-alt-3" /></template>
