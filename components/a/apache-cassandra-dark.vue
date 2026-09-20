<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knh3k_bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knh3k_bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-cassandra-dark" /></template>
