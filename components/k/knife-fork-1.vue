<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-b-5jban.css';
import '../../css/q/q9k8bmnxn.css';
import '../../css/b/bpphhjblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-b-5jban"/><path class="q9k8bmnxn"/><path class="bpphhjblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:knife-fork-1" /></template>
