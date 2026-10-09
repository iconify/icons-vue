<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuk06n_9z.css';
import '../../css/n/ny6l1ubqo.css';
import '../../css/n/n82309b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uuk06n_9z"/><path class="ny6l1ubqo"/><path class="n82309b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jerrycan-48-bold" /></template>
