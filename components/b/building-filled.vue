<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlmneqbga.css';
import '../../css/o/o5_ykjx1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlmneqbga"/><path class="o5_ykjx1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:building-filled" /></template>
