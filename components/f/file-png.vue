<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3mpyzbst.css';
import '../../css/k/ka0ihjbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mpyzbst"/><path class="ka0ihjbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-png" /></template>
