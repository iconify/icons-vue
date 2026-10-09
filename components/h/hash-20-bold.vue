<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvx3ydb_k.css';
import '../../css/n/nov116bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nvx3ydb_k"/><path class="nov116bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hash-20-bold" /></template>
