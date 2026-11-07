<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcgmm_a3s.css';
import '../../css/v/v11avebgt.css';
import '../../css/c/c7jgn5pht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcgmm_a3s"/><path class="v11avebgt"/><path class="c7jgn5pht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-minimalistic-bold" /></template>
