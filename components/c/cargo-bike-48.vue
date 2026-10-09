<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gladqriwb.css';
import '../../css/y/y4lv5l4vm.css';
import '../../css/k/k_e8n9b5o.css';
import '../../css/m/mvd344-pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gladqriwb"/><path class="y4lv5l4vm"/><path class="k_e8n9b5o"/><path class="mvd344-pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-bike-48" /></template>
