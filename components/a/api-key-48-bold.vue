<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqu5shbcg.css';
import '../../css/y/yis3i_jsr.css';
import '../../css/k/kv38rku_j.css';
import '../../css/k/kma9qvbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqu5shbcg"/><path class="yis3i_jsr"/><path class="kv38rku_j"/><path class="kma9qvbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-key-48-bold" /></template>
