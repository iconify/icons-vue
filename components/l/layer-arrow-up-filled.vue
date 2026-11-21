<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufxbcneuu.css';
import '../../css/s/s1ghx-bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufxbcneuu"/><path class="s1ghx-bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layer-arrow-up-filled" /></template>
