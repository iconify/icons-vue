<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmd2tzwfv.css';
import '../../css/c/c_tiz1b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmd2tzwfv"/><path clip-rule="evenodd" class="c_tiz1b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-round-bold" /></template>
