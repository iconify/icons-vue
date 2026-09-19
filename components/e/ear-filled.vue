<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beuj2j22z.css';
import '../../css/l/leb0srb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beuj2j22z"/><path class="leb0srb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ear-filled" /></template>
