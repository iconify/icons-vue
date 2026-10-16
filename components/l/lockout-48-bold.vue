<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9uribkc.css';
import '../../css/k/kl96fjb_a.css';
import '../../css/z/zj2jh3sfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-9uribkc"/><path class="kl96fjb_a"/><path class="zj2jh3sfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockout-48-bold" /></template>
